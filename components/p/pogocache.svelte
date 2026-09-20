<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwp6cxbin.css';
import '../../css/t/t5vikhbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwp6cxbin"/><path class="t5vikhbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pogocache" {...props}></Icon>
