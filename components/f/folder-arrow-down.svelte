<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb0yibb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb0yibb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-arrow-down" {...props}></Icon>
