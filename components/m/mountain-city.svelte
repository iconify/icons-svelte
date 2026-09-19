<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywntjv63r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ywntjv63r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mountain-city" {...props}></Icon>
