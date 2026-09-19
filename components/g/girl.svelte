<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2c1ccccv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l2c1ccccv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl" {...props}></Icon>
