<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyymw5bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vyymw5bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoke-ai-light" {...props}></Icon>
