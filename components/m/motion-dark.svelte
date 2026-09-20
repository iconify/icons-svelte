<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jarw_gnfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1103,"height":386};
const content = `<path class="jarw_gnfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:motion-dark" {...props}></Icon>
