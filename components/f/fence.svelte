<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv3btvbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3btvbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fence" {...props}></Icon>
