<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlq2l5bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlq2l5bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bluesky" {...props}></Icon>
