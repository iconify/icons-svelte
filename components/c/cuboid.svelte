<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gocedot9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gocedot9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cuboid" {...props}></Icon>
