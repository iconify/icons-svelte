<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/motq1qyby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="motq1qyby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contain" {...props}></Icon>
