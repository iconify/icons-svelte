<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtsjshfvz.css';
import '../../css/m/m1cu4sbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mtsjshfvz"/><path class="m1cu4sbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-badge-filled" {...props}></Icon>
