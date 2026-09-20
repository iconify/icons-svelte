<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfowl2b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfowl2b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-d-box-outline" {...props}></Icon>
