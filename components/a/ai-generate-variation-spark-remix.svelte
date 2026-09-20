<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywa31bcfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ywa31bcfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-generate-variation-spark-remix" {...props}></Icon>
