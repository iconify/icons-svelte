<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh6wr9bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh6wr9bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-check-ok-filled" {...props}></Icon>
