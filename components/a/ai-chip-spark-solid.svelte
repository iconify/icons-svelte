<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6tz7dfgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b6tz7dfgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-chip-spark-solid" {...props}></Icon>
