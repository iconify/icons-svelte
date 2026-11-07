<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii24kzbxm.css';
import '../../css/x/xejlx-96v.css';
import '../../css/z/zly6tablv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii24kzbxm"/><path class="xejlx-96v"/><path clip-rule="evenodd" class="zly6tablv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightning-outline" {...props}></Icon>
