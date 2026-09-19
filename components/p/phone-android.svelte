<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5t4xbsr.css';
import '../../css/w/w2xstcbue.css';
import '../../css/r/rq_3jfb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vc5t4xbsr"/><path class="w2xstcbue"/><path class="rq_3jfb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:phone-android" {...props}></Icon>
