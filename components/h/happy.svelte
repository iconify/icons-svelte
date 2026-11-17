<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/a6mwx9v_d.css';
import '../../css/z/z8w34vkig.css';
import '../../css/e/eb6xpzbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="a6mwx9v_d"/><path class="z8w34vkig"/><path class="eb6xpzbjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:happy" {...props}></Icon>
