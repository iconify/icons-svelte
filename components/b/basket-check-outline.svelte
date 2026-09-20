<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhh071ixv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhh071ixv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:basket-check-outline" {...props}></Icon>
