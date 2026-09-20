<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uao541b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uao541b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-network" {...props}></Icon>
