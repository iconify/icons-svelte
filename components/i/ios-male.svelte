<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl6dnvbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl6dnvbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-male" {...props}></Icon>
