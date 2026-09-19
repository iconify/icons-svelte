<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1ebvg0wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="l1ebvg0wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:eye" {...props}></Icon>
