<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg54b2byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="qg54b2byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-gibbous-4" {...props}></Icon>
