<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztdlx5baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdlx5baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-slash-line" {...props}></Icon>
