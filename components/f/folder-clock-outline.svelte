<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alvegvbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alvegvbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-clock-outline" {...props}></Icon>
