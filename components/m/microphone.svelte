<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvhxj1bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lvhxj1bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:microphone" {...props}></Icon>
