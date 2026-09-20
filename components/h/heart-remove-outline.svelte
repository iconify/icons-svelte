<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il_g3sssa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il_g3sssa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-remove-outline" {...props}></Icon>
