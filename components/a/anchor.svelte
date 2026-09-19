<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y492fvb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="y492fvb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:anchor" {...props}></Icon>
