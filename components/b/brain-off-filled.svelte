<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gahn9tbab.css';
import '../../css/r/rpqiizbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gahn9tbab"/><path class="rpqiizbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brain-off-filled" {...props}></Icon>
