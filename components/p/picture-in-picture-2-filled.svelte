<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfa1yjcla.css';
import '../../css/j/j6hyv93_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfa1yjcla"/><path class="j6hyv93_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:picture-in-picture-2-filled" {...props}></Icon>
