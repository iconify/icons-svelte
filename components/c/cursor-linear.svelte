<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzy99uvdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzy99uvdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cursor-linear" {...props}></Icon>
