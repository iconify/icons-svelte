<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcd13orep.css';
import '../../css/z/zs9x5hotx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kcd13orep"/><path class="zs9x5hotx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mongodb-light" {...props}></Icon>
