<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6fsyy90t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1600,"height":1408};
const content = `<path class="z6fsyy90t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:beer" {...props}></Icon>
