<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uob4j6bcx.css';
import '../../css/j/jog-_gb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uob4j6bcx"/><path class="jog-_gb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-heart-filled" {...props}></Icon>
