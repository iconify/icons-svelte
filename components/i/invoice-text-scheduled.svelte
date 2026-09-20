<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaas0deid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaas0deid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-scheduled" {...props}></Icon>
