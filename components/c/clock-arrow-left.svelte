<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj46w8vjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj46w8vjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-arrow-left" {...props}></Icon>
