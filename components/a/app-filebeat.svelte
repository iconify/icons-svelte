<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ln1kbbbbo.css';
import '../../css/y/yef3849lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ln1kbbbbo ouiIcon__fillSecondary"/><path class="yef3849lj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-filebeat" {...props}></Icon>
