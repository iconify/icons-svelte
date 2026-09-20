<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvnie9sjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvnie9sjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-multiple-outline" {...props}></Icon>
