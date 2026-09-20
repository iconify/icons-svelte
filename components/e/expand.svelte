<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh32lacxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh32lacxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:expand" {...props}></Icon>
