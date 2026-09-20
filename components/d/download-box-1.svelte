<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwq82hbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwq82hbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:download-box-1" {...props}></Icon>
