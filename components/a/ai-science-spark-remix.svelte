<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3ji-cbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c3ji-cbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-science-spark-remix" {...props}></Icon>
