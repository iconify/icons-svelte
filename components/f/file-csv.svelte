<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecu067-ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="ecu067-ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:file-csv" {...props}></Icon>
