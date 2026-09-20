<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn4g0qbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn4g0qbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:anchor" {...props}></Icon>
