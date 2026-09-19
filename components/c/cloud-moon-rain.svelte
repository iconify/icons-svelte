<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb3bujb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zb3bujb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cloud-moon-rain" {...props}></Icon>
