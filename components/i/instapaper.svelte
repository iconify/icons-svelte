<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h13n8sbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":488};
const content = `<path class="h13n8sbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:instapaper" {...props}></Icon>
