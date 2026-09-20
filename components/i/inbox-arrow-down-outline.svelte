<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uks-53bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uks-53bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:inbox-arrow-down-outline" {...props}></Icon>
