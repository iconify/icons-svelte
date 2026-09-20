<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pg0no1ryl.css';
import '../../css/l/l52m_-ebg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="pg0no1ryl"/><path class="l52m_-ebg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linecap-round-filled" {...props}></Icon>
