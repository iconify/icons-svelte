<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp2--zv-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp2--zv-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-check-outline" {...props}></Icon>
