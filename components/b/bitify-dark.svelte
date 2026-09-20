<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtcktwbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gtcktwbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitify-dark" {...props}></Icon>
