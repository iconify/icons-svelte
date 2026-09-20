<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw547ccnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw547ccnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:call" {...props}></Icon>
