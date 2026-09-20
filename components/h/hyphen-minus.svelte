<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg9vbp76i.css';
import '../../css/i/ilkd3ex7e.css';
import '../../css/w/wo110wbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zg9vbp76i"/><path class="ilkd3ex7e"/><path class="wo110wbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hyphen-minus" {...props}></Icon>
