<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giby68ztq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="giby68ztq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cloud" {...props}></Icon>
