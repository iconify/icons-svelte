<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s60gkvb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s60gkvb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pc-case-filled" {...props}></Icon>
