<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg_p6bmic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_p6bmic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:parentheses-two-tone" {...props}></Icon>
