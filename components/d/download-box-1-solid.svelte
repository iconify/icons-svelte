<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d78kiv0is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d78kiv0is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:download-box-1-solid" {...props}></Icon>
