<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo8kzlbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lo8kzlbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:artificial-intelligence-spark-remix" {...props}></Icon>
