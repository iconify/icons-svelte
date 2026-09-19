<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b689ubbtl.css';
import '../../css/y/y3f0wgtok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="b689ubbtl"/><path class="y3f0wgtok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:expand" {...props}></Icon>
