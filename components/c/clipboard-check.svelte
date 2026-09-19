<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cogs88p7l.css';
import '../../css/a/a_u4ptbkw.css';
import '../../css/g/gq3c6gp4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cogs88p7l"/><path class="a_u4ptbkw"/><path class="gq3c6gp4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:clipboard-check" {...props}></Icon>
