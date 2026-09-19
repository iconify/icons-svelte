<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f9ykh0zwy.css';
import '../../css/k/kmybmtbiu.css';
import '../../css/u/u5mgnyb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="f9ykh0zwy"/><path class="kmybmtbiu"/><path class="u5mgnyb-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-pouting" {...props}></Icon>
