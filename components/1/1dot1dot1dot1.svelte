<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-4vy0bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-4vy0bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:1dot1dot1dot1" {...props}></Icon>
