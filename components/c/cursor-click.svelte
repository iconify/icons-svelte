<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3jc4r7_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3jc4r7_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cursor-click" {...props}></Icon>
