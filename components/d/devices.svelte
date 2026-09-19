<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otplr3bgs.css';
import '../../css/k/kiwinsf3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="otplr3bgs"/><path class="kiwinsf3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:devices" {...props}></Icon>
