<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh-kc6bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eh-kc6bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maintainerr-light" {...props}></Icon>
