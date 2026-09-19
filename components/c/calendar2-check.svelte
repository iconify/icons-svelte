<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/si8c46vhp.css';
import '../../css/b/b1e4swiah.css';
import '../../css/x/xwj6wumfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="si8c46vhp"/><path class="b1e4swiah"/><path class="xwj6wumfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-check" {...props}></Icon>
