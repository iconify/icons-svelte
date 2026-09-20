<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmex0u96m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmex0u96m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:border-out" {...props}></Icon>
