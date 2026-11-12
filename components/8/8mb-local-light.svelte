<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvyun6ixs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nvyun6ixs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:8mb-local-light" {...props}></Icon>
