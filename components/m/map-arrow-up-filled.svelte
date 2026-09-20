<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ahplb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_ahplb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-arrow-up-filled" {...props}></Icon>
