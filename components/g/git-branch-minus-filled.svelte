<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuam72hri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuam72hri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-branch-minus-filled" {...props}></Icon>
