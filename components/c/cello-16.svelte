<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um4ht9bsf.css';
import '../../css/k/kvdfrrbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="um4ht9bsf"/><path class="kvdfrrbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cello-16" {...props}></Icon>
