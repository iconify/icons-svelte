<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bopebe6hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bopebe6hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-key-line" {...props}></Icon>
