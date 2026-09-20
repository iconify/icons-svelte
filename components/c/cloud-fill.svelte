<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh72ehbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wh72ehbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-fill" {...props}></Icon>
