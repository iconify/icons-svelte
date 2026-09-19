<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/klebjebfq.css';
import '../../css/b/bacj-obey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><circle class="klebjebfq"/><path class="bacj-obey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eye-fill-12" {...props}></Icon>
