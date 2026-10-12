<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy37fwx1z.css';
import '../../css/a/aqrtcbb7a.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy37fwx1z"/><path class="aqrtcbb7a"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-box-filled" {...props}></Icon>
