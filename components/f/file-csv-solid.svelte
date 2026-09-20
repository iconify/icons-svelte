<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtllsvb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gtllsvb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-csv-solid" {...props}></Icon>
