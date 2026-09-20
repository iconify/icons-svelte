<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvmis9xnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvmis9xnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:netgear" {...props}></Icon>
