<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7uinz_wv.css';
import '../../css/m/my4v-7bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7uinz_wv"/><path class="my4v-7bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:riverside-fm" {...props}></Icon>
