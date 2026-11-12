<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biz38_b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="biz38_b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cyberhaven-light" {...props}></Icon>
