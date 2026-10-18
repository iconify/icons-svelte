<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-vkd2r7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-vkd2r7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-off" {...props}></Icon>
