<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj49vpb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="kj49vpb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone" {...props}></Icon>
