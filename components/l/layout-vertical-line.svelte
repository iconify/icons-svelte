<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fapd8595a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fapd8595a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-vertical-line" {...props}></Icon>
