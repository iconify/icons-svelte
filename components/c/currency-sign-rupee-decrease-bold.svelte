<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0_xjvx6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0_xjvx6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:currency-sign-rupee-decrease-bold" {...props}></Icon>
