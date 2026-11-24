<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvgr08bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvgr08bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:footprints-filled" {...props}></Icon>
