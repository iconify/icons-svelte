<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxn26mb9t.css';
import '../../css/a/aekfktbaf.css';
import '../../css/r/r0qeryp2j.css';
import '../../css/f/fiqncj_tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jxn26mb9t"/><path class="aekfktbaf"/><path class="r0qeryp2j"/><path class="fiqncj_tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bench-vice-48" {...props}></Icon>
