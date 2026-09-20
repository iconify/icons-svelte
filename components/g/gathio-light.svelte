<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9ywkvrys.css';
import '../../css/y/ybd0ybb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9ywkvrys"/><path class="ybd0ybb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gathio-light" {...props}></Icon>
