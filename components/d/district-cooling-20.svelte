<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svs32pbol.css';
import '../../css/w/wsv6h_otb.css';
import '../../css/n/neih8ubcu.css';
import '../../css/w/w6fbvubyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="svs32pbol"/><path class="wsv6h_otb"/><path class="neih8ubcu"/><path class="w6fbvubyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:district-cooling-20" {...props}></Icon>
