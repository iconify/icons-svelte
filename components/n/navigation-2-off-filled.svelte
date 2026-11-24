<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw-2n_btc.css';
import '../../css/g/gawagji8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw-2n_btc"/><path clip-rule="evenodd" class="gawagji8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:navigation-2-off-filled" {...props}></Icon>
