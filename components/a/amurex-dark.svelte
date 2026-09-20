<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg3759byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fg3759byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amurex-dark" {...props}></Icon>
