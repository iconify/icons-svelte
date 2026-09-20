<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9-ad9g8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9-ad9g8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-sorted-down" {...props}></Icon>
