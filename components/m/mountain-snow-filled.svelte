<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp5fi2byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp5fi2byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mountain-snow-filled" {...props}></Icon>
