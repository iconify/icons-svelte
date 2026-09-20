<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z42gu4bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z42gu4bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-technology-spark-remix" {...props}></Icon>
