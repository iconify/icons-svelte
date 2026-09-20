<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp0doc0sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp0doc0sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lollipop-fill" {...props}></Icon>
