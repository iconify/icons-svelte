<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufej49noq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufej49noq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:powerschool-dark" {...props}></Icon>
