<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4_b6xb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4_b6xb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lungs-line" {...props}></Icon>
