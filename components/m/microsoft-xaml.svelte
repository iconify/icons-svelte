<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltuf3vbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltuf3vbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-xaml" {...props}></Icon>
