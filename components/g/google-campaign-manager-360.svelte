<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iamlc8_rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iamlc8_rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-campaign-manager-360" {...props}></Icon>
