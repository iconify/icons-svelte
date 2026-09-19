<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owboirb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="owboirb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:road" {...props}></Icon>
