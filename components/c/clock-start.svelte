<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nta5e4bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nta5e4bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-start" {...props}></Icon>
