<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx6xl1bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx6xl1bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:backbonedotjs" {...props}></Icon>
