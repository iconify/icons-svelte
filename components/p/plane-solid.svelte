<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv5z_obdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv5z_obdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plane-solid" {...props}></Icon>
