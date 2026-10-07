<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iju81lxdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iju81lxdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:custom-link" {...props}></Icon>
