<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx2-hcb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx2-hcb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:podcast-index-dark" {...props}></Icon>
