<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj9vw7x9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="nj9vw7x9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:road-bridge" {...props}></Icon>
