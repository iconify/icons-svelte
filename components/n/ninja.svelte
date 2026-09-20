<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af99qwqhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="af99qwqhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ninja" {...props}></Icon>
