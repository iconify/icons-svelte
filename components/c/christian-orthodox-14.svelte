<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou116yntr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ou116yntr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:christian-orthodox-14" {...props}></Icon>
