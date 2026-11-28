<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-k7cf_7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s-k7cf_7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drafting-compass-duotone" {...props}></Icon>
