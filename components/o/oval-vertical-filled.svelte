<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds5bglbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds5bglbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:oval-vertical-filled" {...props}></Icon>
