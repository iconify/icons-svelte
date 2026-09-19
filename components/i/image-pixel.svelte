<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siiby4bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="siiby4bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:image-pixel" {...props}></Icon>
