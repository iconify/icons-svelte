<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t91r2hsug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t91r2hsug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:build-definition" {...props}></Icon>
