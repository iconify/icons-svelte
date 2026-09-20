<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofp1v6byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofp1v6byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:filter-2-line" {...props}></Icon>
