<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_8iubmh.css';
import '../../css/c/cl2ahfl2g.css';
import '../../css/n/nc-y7w9wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1_8iubmh"/><path class="cl2ahfl2g"/><path class="nc-y7w9wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:litellm" {...props}></Icon>
