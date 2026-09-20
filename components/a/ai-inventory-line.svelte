<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_cnb8bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_cnb8bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-inventory-line" {...props}></Icon>
