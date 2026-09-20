<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdszi2i9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gdszi2i9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ai-generate-portrait-image-spark-remix" {...props}></Icon>
