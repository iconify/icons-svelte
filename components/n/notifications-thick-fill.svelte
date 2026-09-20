<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keux-obrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="keux-obrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-thick-fill" {...props}></Icon>
