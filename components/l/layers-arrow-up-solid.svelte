<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcvifnb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcvifnb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-arrow-up-solid" {...props}></Icon>
