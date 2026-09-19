<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p0hgbgb9d.css';
import '../../css/e/eumqw-b2u.css';
import '../../css/c/cmpm5kb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p0hgbgb9d"/><path class="eumqw-b2u"/><path clip-rule="evenodd" class="cmpm5kb0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-b-p" {...props}></Icon>
