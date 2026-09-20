<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bej3u-s3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bej3u-s3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-generate-portrait-image-spark-remix" {...props}></Icon>
