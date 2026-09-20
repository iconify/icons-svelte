<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytc_j7pdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytc_j7pdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-view-outline" {...props}></Icon>
