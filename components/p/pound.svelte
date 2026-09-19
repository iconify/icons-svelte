<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dubu0bb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="dubu0bb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:pound" {...props}></Icon>
