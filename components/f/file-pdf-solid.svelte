<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq335obzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq335obzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-pdf-solid" {...props}></Icon>
