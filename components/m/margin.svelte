<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsgg_6xrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsgg_6xrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:margin" {...props}></Icon>
