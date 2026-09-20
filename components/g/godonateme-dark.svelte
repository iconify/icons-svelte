<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phqcd--ip.css';
import '../../css/n/n5tl80b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="phqcd--ip"/><path class="n5tl80b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:godonateme-dark" {...props}></Icon>
