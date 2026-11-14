<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-crgbb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-crgbb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-09" {...props}></Icon>
