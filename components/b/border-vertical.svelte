<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff2d-me7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff2d-me7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-vertical" {...props}></Icon>
