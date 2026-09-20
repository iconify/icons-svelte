<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rct38-bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rct38-bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-left-outline" {...props}></Icon>
