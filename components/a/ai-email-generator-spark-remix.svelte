<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvyksh09g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hvyksh09g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-email-generator-spark-remix" {...props}></Icon>
