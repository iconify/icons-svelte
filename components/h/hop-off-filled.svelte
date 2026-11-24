<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjymy35eq.css';
import '../../css/w/w966wlbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjymy35eq"/><path class="w966wlbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hop-off-filled" {...props}></Icon>
