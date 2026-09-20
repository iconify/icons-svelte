<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0bdxl2ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0bdxl2ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:books-plus" {...props}></Icon>
