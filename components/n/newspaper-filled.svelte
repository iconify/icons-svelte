<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr46c6bmn.css';
import '../../css/v/v5th-uitq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr46c6bmn"/><path clip-rule="evenodd" class="v5th-uitq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:newspaper-filled" {...props}></Icon>
