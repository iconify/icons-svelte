<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz5hisb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sz5hisb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ferron-light" {...props}></Icon>
