<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gebj2bpbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gebj2bpbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-arrow-right-outline" {...props}></Icon>
