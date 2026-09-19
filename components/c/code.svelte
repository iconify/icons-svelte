<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4pg7ir2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":769};
const content = `<path class="x4pg7ir2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:code" {...props}></Icon>
