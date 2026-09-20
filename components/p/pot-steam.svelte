<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ne6ab_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ne6ab_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pot-steam" {...props}></Icon>
