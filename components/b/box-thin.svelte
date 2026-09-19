<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns3mo6bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns3mo6bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:box-thin" {...props}></Icon>
