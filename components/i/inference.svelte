<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvjlo7o6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvjlo7o6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inference" {...props}></Icon>
