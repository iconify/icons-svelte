<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoof9ubgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoof9ubgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-unknown-fill" {...props}></Icon>
