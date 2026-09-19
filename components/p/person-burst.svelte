<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjy9ebcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fjy9ebcfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-burst" {...props}></Icon>
