<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btsdemx5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btsdemx5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-sync-outline" {...props}></Icon>
