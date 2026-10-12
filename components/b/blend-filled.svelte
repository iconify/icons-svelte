<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvhkvuiza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zvhkvuiza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:blend-filled" {...props}></Icon>
