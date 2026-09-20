<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/d5wgp4bfy.css';
import '../../css/g/gu5hqxbkc.css';
import '../../css/l/lrfx45bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="d5wgp4bfy"/><path class="gu5hqxbkc"/><path class="lrfx45bzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:paginate-filter-music" {...props}></Icon>
