<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sui4_vb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sui4_vb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:puzzle" {...props}></Icon>
