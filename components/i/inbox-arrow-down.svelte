<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg2tfubdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg2tfubdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:inbox-arrow-down" {...props}></Icon>
