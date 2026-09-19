<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahz1tzslr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ahz1tzslr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:fast-forward-one-x" {...props}></Icon>
