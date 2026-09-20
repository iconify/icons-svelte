<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndub7cbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndub7cbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codeigniter-logo-solid" {...props}></Icon>
