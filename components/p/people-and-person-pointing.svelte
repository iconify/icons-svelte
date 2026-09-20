<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvw6ufsvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dvw6ufsvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-and-person-pointing" {...props}></Icon>
