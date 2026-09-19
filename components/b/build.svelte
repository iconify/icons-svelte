<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pytq4bb0c.css';
import '../../css/v/vtc4ipbzp.css';
import '../../css/n/neygi1gkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="pytq4bb0c"/><path class="vtc4ipbzp"/><path class="neygi1gkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:build" {...props}></Icon>
