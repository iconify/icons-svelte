<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qegn1_8ui.css';
import '../../css/w/w0dhn7mec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qegn1_8ui"/><path class="w0dhn7mec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:megaphone-off-filled" {...props}></Icon>
