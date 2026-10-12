<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edfoyo7yi.css';
import '../../css/c/c1uddcbcz.css';
import '../../css/z/zc_h-6bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edfoyo7yi"/><path class="c1uddcbcz"/><path class="zc_h-6bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-search-filled" {...props}></Icon>
