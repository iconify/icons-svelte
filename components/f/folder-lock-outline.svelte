<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwefysk2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwefysk2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-lock-outline" {...props}></Icon>
