<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdc0kfbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdc0kfbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-sync-outline" {...props}></Icon>
