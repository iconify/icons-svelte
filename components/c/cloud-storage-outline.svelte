<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx3h3z0iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx3h3z0iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:cloud-storage-outline" {...props}></Icon>
