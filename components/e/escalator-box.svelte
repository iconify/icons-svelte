<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm9f6lmtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm9f6lmtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:escalator-box" {...props}></Icon>
