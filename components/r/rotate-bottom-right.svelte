<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob843kbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob843kbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-bottom-right" {...props}></Icon>
