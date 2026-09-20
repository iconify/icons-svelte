<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l07610gvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l07610gvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dify-light" {...props}></Icon>
