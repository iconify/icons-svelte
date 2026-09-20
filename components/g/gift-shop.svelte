<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-ft4gl8r.css';
import '../../css/n/nn7iw1brc.css';
import '../../css/z/zackx91ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="n-ft4gl8r"/><path class="nn7iw1brc"/><path class="zackx91ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:gift-shop" {...props}></Icon>
