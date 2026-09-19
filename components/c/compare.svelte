<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzpkb4b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jzpkb4b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:compare" {...props}></Icon>
