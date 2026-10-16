<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjj-1pc-n.css';
import '../../css/y/ynpxxgbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xjj-1pc-n"/><path class="ynpxxgbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mailbox-20-bold" {...props}></Icon>
