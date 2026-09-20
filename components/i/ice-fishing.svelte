<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygne6q0py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ygne6q0py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:ice-fishing" {...props}></Icon>
