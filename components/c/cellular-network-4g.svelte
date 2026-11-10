<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv4316bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv4316bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cellular-network-4g" {...props}></Icon>
