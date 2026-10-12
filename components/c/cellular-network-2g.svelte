<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4el2fric.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4el2fric"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cellular-network-2g" {...props}></Icon>
