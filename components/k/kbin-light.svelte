<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq3m-xb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kq3m-xb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kbin-light" {...props}></Icon>
