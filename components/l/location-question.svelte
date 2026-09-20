<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa0g-um8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa0g-um8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-question" {...props}></Icon>
