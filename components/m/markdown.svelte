<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3o8y58fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a3o8y58fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:markdown" {...props}></Icon>
