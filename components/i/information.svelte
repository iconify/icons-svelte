<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkn1_fb_t.css';
import '../../css/g/gzawnq-ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="bkn1_fb_t"/><path class="gzawnq-ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:information" {...props}></Icon>
