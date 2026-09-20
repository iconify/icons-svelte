<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/panl95b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="panl95b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-email-generator-spark-solid" {...props}></Icon>
