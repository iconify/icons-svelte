<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zagj-zb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zagj-zb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:chart-scatter" {...props}></Icon>
