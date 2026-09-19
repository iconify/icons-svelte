<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmny2jbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":520};
const content = `<path class="pmny2jbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:boiled-egg-finger" {...props}></Icon>
