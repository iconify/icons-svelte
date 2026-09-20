<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo1t82bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo1t82bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:compass" {...props}></Icon>
