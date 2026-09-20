<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba82wobrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba82wobrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-multiple-outline" {...props}></Icon>
