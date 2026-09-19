<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhsl0kbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhsl0kbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevron-right-square" {...props}></Icon>
