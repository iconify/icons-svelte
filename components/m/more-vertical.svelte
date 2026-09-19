<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m16mtllzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m16mtllzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:more-vertical" {...props}></Icon>
