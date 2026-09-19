<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s40qgyyak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s40qgyyak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cloud-off-solid" {...props}></Icon>
