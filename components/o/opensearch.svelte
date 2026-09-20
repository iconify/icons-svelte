<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bll1o-bzb.css';
import '../../css/v/v-kzk1h6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bll1o-bzb"/><path class="v-kzk1h6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensearch" {...props}></Icon>
