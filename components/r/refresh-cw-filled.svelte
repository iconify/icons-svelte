<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nppc4ldyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nppc4ldyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:refresh-cw-filled" {...props}></Icon>
