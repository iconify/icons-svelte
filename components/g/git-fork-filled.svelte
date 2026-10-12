<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb_9fkb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb_9fkb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-fork-filled" {...props}></Icon>
