<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1gl7fbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1gl7fbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:presentation-audience" {...props}></Icon>
