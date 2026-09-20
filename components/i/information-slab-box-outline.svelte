<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9qw-lb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9qw-lb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:information-slab-box-outline" {...props}></Icon>
