<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0119uc7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="h0119uc7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:heart-circle-exclamation" {...props}></Icon>
