<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn-5w0b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fn-5w0b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrow-tall-up-left" {...props}></Icon>
