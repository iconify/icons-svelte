<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjljwei0o.css';
import '../../css/g/ghw7-wbwc.css';
import '../../css/b/b_vy63bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cjljwei0o"/><path class="ghw7-wbwc"/><path class="b_vy63bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brick-wall-20-bold" {...props}></Icon>
