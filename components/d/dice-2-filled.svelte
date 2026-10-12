<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgma3pasw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgma3pasw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dice-2-filled" {...props}></Icon>
