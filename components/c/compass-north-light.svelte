<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/b/b-r8pffbr.css';
import '../../css/i/iina63bcq.css';
import '../../css/c/c9w1ambxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="b-r8pffbr"/><path class="iina63bcq"/><path class="c9w1ambxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:compass-north-light" {...props}></Icon>
