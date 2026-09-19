<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc9b90bna.css';
import '../../css/y/ysh5xgerc.css';
import '../../css/p/po0txjbom.css';
import '../../css/n/nl7257qqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="xc9b90bna"><path class="ysh5xgerc"/><ellipse class="po0txjbom"/><path class="nl7257qqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:music-list-bold" {...props}></Icon>
