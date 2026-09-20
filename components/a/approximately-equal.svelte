<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irs-1rb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irs-1rb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:approximately-equal" {...props}></Icon>
