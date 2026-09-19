<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-jvlk71h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d-jvlk71h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:ascending" {...props}></Icon>
