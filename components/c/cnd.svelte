<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tewz0pbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tewz0pbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cnd" {...props}></Icon>
