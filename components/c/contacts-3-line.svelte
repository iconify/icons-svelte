<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc4pz-6xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc4pz-6xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-3-line" {...props}></Icon>
