<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggkt217da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ggkt217da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:medical-files-report-history-remix" {...props}></Icon>
