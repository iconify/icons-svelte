<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iohu4wb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iohu4wb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-edit" {...props}></Icon>
