<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyuy5z9fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyuy5z9fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:glass-water-solid" {...props}></Icon>
