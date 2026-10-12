<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hchrethjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hchrethjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-tree-filled" {...props}></Icon>
