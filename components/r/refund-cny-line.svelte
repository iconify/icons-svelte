<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3qp9_dtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3qp9_dtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refund-cny-line" {...props}></Icon>
