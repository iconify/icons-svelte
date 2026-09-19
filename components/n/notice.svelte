<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxj8s_bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxj8s_bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:notice" {...props}></Icon>
