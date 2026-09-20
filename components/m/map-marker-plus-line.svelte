<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umx9k2iuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umx9k2iuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:map-marker-plus-line" {...props}></Icon>
