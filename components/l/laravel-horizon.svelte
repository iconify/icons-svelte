<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_4gtvbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_4gtvbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:laravel-horizon" {...props}></Icon>
