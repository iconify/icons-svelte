<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tza4e1wgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tza4e1wgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-edit-spark-solid" {...props}></Icon>
