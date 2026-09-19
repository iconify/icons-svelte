<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk21cmshl.css';
import '../../css/t/tyqxa-33r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk21cmshl"/><path class="tyqxa-33r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:developer-portal" {...props}></Icon>
