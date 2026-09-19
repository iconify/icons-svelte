<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q17hu-xfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q17hu-xfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:camera-on-rectangle-fill" {...props}></Icon>
