<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9s38sb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b9s38sb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:1inch" {...props}></Icon>
