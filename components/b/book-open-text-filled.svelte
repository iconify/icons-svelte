<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clrvqab_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clrvqab_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-open-text-filled" {...props}></Icon>
