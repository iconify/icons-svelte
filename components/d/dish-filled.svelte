<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_o3b9txh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_o3b9txh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dish-filled" {...props}></Icon>
