<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wibr-cbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wibr-cbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-z-a" {...props}></Icon>
