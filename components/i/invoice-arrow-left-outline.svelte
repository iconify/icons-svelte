<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkkze058o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkkze058o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-arrow-left-outline" {...props}></Icon>
