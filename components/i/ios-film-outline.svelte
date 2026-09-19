<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtxc1y5_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtxc1y5_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-film-outline" {...props}></Icon>
