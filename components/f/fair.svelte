<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aki9-bctd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aki9-bctd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:fair" {...props}></Icon>
