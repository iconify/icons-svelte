<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c48_sfsxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c48_sfsxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pyshelf-dark" {...props}></Icon>
