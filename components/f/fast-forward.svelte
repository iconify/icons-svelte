<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr69ofbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr69ofbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fast-forward" {...props}></Icon>
