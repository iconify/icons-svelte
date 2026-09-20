<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmir9_bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmir9_bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:juce" {...props}></Icon>
