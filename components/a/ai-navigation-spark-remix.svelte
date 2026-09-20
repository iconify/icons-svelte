<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enm7a0b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="enm7a0b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-navigation-spark-remix" {...props}></Icon>
