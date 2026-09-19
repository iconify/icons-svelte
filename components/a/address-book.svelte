<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd8fe119i.css';
import '../../css/q/qk5s2wd5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cd8fe119i"/><path class="qk5s2wd5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:address-book" {...props}></Icon>
