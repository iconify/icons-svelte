<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqwnpkb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hqwnpkb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:lock-12" {...props}></Icon>
