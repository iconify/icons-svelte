<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p08wz6epf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p08wz6epf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:anchor-solid" {...props}></Icon>
