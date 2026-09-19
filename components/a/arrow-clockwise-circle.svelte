<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq4f1ncey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bq4f1ncey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-clockwise-circle" {...props}></Icon>
