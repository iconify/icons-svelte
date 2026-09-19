<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz57-0xqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gz57-0xqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:brush" {...props}></Icon>
