<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkgs2j2gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qkgs2j2gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:feedback-request-solid" {...props}></Icon>
