<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpe_t7bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpe_t7bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-expand-down" {...props}></Icon>
