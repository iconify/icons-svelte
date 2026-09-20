<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj_tfjbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sj_tfjbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:download-box-1-remix" {...props}></Icon>
