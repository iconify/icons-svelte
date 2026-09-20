<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vst9gbbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vst9gbbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:activity-sharp-two-tone" {...props}></Icon>
