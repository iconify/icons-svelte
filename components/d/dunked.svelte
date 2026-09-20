<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfqzb-bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfqzb-bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dunked" {...props}></Icon>
