<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcdy3zbpl.css';
import '../../css/j/jd002rb2b.css';
import '../../css/p/pdau_gb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="kcdy3zbpl"/><path class="jd002rb2b"/><path class="pdau_gb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:fallen-leaf" {...props}></Icon>
