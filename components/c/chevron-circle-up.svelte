<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5ku5msfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="l5ku5msfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chevron-circle-up" {...props}></Icon>
