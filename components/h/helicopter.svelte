<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtksn9bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qtksn9bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:helicopter" {...props}></Icon>
