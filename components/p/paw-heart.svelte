<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yogix9bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yogix9bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:paw-heart" {...props}></Icon>
