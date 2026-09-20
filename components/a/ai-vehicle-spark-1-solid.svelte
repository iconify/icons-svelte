<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8-dsox2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h8-dsox2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-vehicle-spark-1-solid" {...props}></Icon>
