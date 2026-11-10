<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uexx9pivj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uexx9pivj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:python" {...props}></Icon>
