<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks4-i1l3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks4-i1l3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-filled" {...props}></Icon>
