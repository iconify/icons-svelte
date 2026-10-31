<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgwxuac0h.css';
import '../../css/b/bbzbypbsp.css';
import '../../css/w/wpc3x9bjb.css';
import '../../css/z/zx_78cd7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cgwxuac0h"/><path class="bbzbypbsp"/><path class="wpc3x9bjb"/><path class="zx_78cd7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:oregano" {...props}></Icon>
