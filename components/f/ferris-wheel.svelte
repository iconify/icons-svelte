<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc0vyvbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc0vyvbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ferris-wheel" {...props}></Icon>
