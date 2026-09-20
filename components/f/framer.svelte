<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpk25w8xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpk25w8xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:framer" {...props}></Icon>
