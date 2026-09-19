<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8t-bxbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8t-bxbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:home-simple-door" {...props}></Icon>
