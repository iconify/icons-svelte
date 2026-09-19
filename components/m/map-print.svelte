<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/br4v2hbup.css';
import '../../css/c/cn83yka1u.css';
import '../../css/e/em1xsmxvw.css';
import '../../css/e/ea3emzk3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="br4v2hbup"/><path clip-rule="evenodd" class="cn83yka1u"/><path clip-rule="evenodd" class="em1xsmxvw"/><path class="ea3emzk3u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:map-print" {...props}></Icon>
