<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyerzhc-f.css';
import '../../css/t/t6lf1fb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iyerzhc-f"/><path class="t6lf1fb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:reading-lamp" {...props}></Icon>
