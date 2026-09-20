<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n86eppbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n86eppbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-pause-outline" {...props}></Icon>
