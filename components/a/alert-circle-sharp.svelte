<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqy2g75wd.css';
import '../../css/b/bm9qtjbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bqy2g75wd"/><path class="bm9qtjbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:alert-circle-sharp" {...props}></Icon>
