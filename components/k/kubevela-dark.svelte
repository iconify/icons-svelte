<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmakjdpxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":122.5,"height":122.5};
const content = `<path class="xmakjdpxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kubevela-dark" {...props}></Icon>
