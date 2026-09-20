<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kymer5dgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kymer5dgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:add" {...props}></Icon>
