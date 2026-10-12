<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7__prbvz.css';
import '../../css/v/vykt_qbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7__prbvz"/><path clip-rule="evenodd" class="vykt_qbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-search-2-filled" {...props}></Icon>
