<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_w_6qbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_w_6qbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-right-square-fill" {...props}></Icon>
