<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6v7mcc5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6v7mcc5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comma-circle" {...props}></Icon>
