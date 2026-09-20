<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aha9_lkxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aha9_lkxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-science-spark-solid" {...props}></Icon>
