<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbdlflbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rbdlflbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-cloud-spark-solid" {...props}></Icon>
