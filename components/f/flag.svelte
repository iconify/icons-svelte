<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpx2wv53c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gpx2wv53c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flag" {...props}></Icon>
