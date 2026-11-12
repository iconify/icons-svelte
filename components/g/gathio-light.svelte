<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9ywkvrys.css';
import '../../css/v/vzun6nk-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9ywkvrys"/><path class="vzun6nk-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gathio-light" {...props}></Icon>
