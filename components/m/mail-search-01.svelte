<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/u/ualj8xbvx.css';
import '../../css/t/tcrnivb-g.css';
import '../../css/b/b4xx4tb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="ualj8xbvx"/><path class="tcrnivb-g"/><path class="b4xx4tb1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-search-01" {...props}></Icon>
