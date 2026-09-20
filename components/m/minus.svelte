<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj9892bvm.css';
import '../../css/w/wo110wbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tj9892bvm"/><path class="wo110wbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:minus" {...props}></Icon>
