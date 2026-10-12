<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vukzqzkbe.css';
import '../../css/p/p_hkdzbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vukzqzkbe"/><path class="p_hkdzbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:notebook-dot-filled" {...props}></Icon>
