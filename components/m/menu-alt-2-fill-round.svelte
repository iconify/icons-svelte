<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5jngf2xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5jngf2xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-2-fill-round" {...props}></Icon>
