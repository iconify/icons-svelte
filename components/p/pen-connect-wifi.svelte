<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyx6_8qkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyx6_8qkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pen-connect-wifi" {...props}></Icon>
