<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za6id5nae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="za6id5nae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillesix" {...props}></Icon>
