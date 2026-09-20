<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9qu2hl1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50.6,"height":48};
const content = `<path class="w9qu2hl1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:honeycomb" {...props}></Icon>
