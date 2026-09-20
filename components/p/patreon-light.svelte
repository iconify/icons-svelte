<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wti_j-baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":40};
const content = `<path class="wti_j-baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:patreon-light" {...props}></Icon>
