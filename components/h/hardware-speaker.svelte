<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gapaz2bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gapaz2bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hardware-speaker" {...props}></Icon>
