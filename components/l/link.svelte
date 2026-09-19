<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a95pulbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a95pulbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:link" {...props}></Icon>
