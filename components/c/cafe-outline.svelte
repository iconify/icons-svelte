<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0kfxub6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0kfxub6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cafe-outline" {...props}></Icon>
