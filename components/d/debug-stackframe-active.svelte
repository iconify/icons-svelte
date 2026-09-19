<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b-gt9_21o.css';
import '../../css/w/wgo9jkn8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="b-gt9_21o"/><path class="wgo9jkn8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-stackframe-active" {...props}></Icon>
