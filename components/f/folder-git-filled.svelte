<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgj9anbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgj9anbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-git-filled" {...props}></Icon>
