<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfl__x7jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfl__x7jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dydx" {...props}></Icon>
