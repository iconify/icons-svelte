<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvngkmbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvngkmbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rimac-automobili" {...props}></Icon>
