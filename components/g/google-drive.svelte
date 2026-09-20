<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb1bdbcsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wb1bdbcsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:google-drive" {...props}></Icon>
