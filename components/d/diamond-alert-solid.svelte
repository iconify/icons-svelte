<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4k1qp8kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4k1qp8kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:diamond-alert-solid" {...props}></Icon>
