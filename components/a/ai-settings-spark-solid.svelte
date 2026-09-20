<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ius_95bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ius_95bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-settings-spark-solid" {...props}></Icon>
