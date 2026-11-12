<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugrv1ixqz.css';
import '../../css/y/ylok2ab9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugrv1ixqz"/><path class="ylok2ab9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ironcalc" {...props}></Icon>
