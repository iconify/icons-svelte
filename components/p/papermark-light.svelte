<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy0i9f5du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qy0i9f5du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermark-light" {...props}></Icon>
