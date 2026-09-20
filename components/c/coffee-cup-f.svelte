<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa8bghbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="fa8bghbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:coffee-cup-f" {...props}></Icon>
