<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm5w17bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qm5w17bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:download-file-solid" {...props}></Icon>
