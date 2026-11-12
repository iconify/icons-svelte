<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0nj5mbku.css';
import '../../css/z/zs9x5hotx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k0nj5mbku"/><path class="zs9x5hotx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mongodb-light" {...props}></Icon>
