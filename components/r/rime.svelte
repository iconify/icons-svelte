<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxew7j2zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxew7j2zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rime" {...props}></Icon>
