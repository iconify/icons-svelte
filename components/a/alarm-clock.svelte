<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u86znlbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u86znlbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:alarm-clock" {...props}></Icon>
