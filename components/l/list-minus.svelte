<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zam2drdnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zam2drdnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-minus" {...props}></Icon>
