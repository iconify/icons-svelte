<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzrjrrb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzrjrrb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:broccoli" {...props}></Icon>
