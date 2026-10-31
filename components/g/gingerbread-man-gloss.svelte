<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvv27jbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvv27jbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gingerbread-man-gloss" {...props}></Icon>
