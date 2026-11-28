<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq7mlebuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq7mlebuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:basket-x" {...props}></Icon>
