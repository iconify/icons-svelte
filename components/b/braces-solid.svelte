<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w65ko2ctp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w65ko2ctp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:braces-solid" {...props}></Icon>
