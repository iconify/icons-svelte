<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0z666bnz.css';
import '../../css/l/l2skeeb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0z666bnz"/><path class="l2skeeb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:duplicate" {...props}></Icon>
