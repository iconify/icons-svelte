<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo1rnqugs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yo1rnqugs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bee-fill" {...props}></Icon>
