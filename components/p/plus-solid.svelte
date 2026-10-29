<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmc7o3bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmc7o3bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plus-solid" {...props}></Icon>
