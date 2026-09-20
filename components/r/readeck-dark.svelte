<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp2cfrbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wp2cfrbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:readeck-dark" {...props}></Icon>
