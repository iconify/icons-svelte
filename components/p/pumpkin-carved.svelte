<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_u21gbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_u21gbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pumpkin-carved" {...props}></Icon>
