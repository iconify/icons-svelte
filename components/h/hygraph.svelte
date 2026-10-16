<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrnudiz8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":55};
const content = `<path class="rrnudiz8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hygraph" {...props}></Icon>
