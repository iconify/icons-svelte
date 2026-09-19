<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy44idbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gy44idbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dat" {...props}></Icon>
