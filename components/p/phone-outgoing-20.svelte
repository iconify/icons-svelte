<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2m65bbab.css';
import '../../css/u/uza837t1m.css';
import '../../css/a/an5pwtbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2m65bbab"/><path class="uza837t1m"/><path class="an5pwtbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-outgoing-20" {...props}></Icon>
