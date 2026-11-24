<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz6p2kbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz6p2kbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brush-filled" {...props}></Icon>
