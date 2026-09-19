<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfm_umb2w.css';
import '../../css/z/zjqxlr-ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfm_umb2w"/><path clip-rule="evenodd" class="zjqxlr-ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:gift-filled" {...props}></Icon>
