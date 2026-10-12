<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntu5cfbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntu5cfbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-input-filled" {...props}></Icon>
