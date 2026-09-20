<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgjbtjbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgjbtjbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medusa-dark" {...props}></Icon>
