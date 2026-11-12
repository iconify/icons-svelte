<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y540id84w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y540id84w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentofu-dark" {...props}></Icon>
