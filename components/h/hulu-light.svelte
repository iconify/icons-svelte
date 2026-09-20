<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trlfrfbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":243.5,"height":80};
const content = `<path clip-rule="evenodd" class="trlfrfbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hulu-light" {...props}></Icon>
