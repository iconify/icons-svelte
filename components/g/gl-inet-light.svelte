<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me-ycib7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="me-ycib7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gl-inet-light" {...props}></Icon>
