<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv2o3kbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv2o3kbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-animate-logo-solid" {...props}></Icon>
