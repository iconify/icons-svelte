<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgio3ubzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgio3ubzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-minus-filled" {...props}></Icon>
