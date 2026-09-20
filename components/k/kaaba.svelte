<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro1l_sqac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ro1l_sqac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:kaaba" {...props}></Icon>
