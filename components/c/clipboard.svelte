<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bisfgdhuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bisfgdhuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:clipboard" {...props}></Icon>
