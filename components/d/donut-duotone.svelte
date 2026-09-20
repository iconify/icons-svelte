<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nmf9j0bku.css';
import '../../css/i/ili4i0bdu.css';
import '../../css/e/ef8fzorxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nmf9j0bku"/><path class="ili4i0bdu"/><path class="ef8fzorxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:donut-duotone" {...props}></Icon>
