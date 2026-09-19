<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwa9ygbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwa9ygbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:beach-bag-big" {...props}></Icon>
