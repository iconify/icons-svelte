<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjroy5biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="hjroy5biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:file-share-2-solid" {...props}></Icon>
