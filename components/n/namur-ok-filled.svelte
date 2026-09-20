<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqj-w3bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xqj-w3bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:namur-ok-filled" {...props}></Icon>
