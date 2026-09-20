<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy01kxb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy01kxb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:boeing" {...props}></Icon>
