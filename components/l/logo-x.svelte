<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsuq6xb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zsuq6xb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-x" {...props}></Icon>
