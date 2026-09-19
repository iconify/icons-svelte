<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vszaobclx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vszaobclx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ai-flow-filled" {...props}></Icon>
