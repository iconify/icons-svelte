<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taogx-qgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="taogx-qgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:golf-ball" {...props}></Icon>
