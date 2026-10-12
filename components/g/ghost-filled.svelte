<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao6xx6nbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ao6xx6nbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ghost-filled" {...props}></Icon>
