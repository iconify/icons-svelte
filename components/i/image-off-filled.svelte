<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewyuo1s9g.css';
import '../../css/w/wvjpim6nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewyuo1s9g"/><path class="wvjpim6nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-off-filled" {...props}></Icon>
