<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn2pokbmn.css';
import '../../css/x/x83nf7g0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn2pokbmn"/><path class="x83nf7g0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-upload-filled" {...props}></Icon>
