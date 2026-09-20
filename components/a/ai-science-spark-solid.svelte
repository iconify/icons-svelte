<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaxphm5ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qaxphm5ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-science-spark-solid" {...props}></Icon>
