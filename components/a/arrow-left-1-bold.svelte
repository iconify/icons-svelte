<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9qfofobu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9qfofobu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-1-bold" {...props}></Icon>
