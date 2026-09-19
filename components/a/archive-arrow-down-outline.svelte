<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5rxtxb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5rxtxb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:archive-arrow-down-outline" {...props}></Icon>
