<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur2i2bh8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ur2i2bh8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:delta-air-lines-light" {...props}></Icon>
