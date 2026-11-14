<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhnm9mbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhnm9mbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delete-01" {...props}></Icon>
