<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dypydkbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dypydkbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-snow-solid" {...props}></Icon>
