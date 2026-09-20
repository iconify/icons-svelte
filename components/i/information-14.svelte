<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhwxi5bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rhwxi5bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:information-14" {...props}></Icon>
