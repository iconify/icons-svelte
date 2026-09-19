<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a18h3goli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="a18h3goli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:battery-half" {...props}></Icon>
