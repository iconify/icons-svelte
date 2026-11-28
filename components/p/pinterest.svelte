<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/ggubv6whl.css';
import '../../css/f/f9iip8bgg.css';
import '../../css/p/pf73p7kxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ggubv6whl"/><path class="f9iip8bgg"/><path class="pf73p7kxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pinterest" {...props}></Icon>
