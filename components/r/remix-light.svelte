<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljgadcc1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ljgadcc1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:remix-light" {...props}></Icon>
