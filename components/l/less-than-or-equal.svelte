<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ondrem6qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ondrem6qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:less-than-or-equal" {...props}></Icon>
