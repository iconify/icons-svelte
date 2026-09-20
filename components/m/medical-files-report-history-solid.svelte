<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igndbzb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="igndbzb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:medical-files-report-history-solid" {...props}></Icon>
