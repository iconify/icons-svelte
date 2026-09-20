<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2_xeebfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_xeebfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-sync-outline" {...props}></Icon>
