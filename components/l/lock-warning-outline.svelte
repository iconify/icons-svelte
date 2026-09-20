<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6n_f-bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6n_f-bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-warning-outline" {...props}></Icon>
