<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j1-l-5b8u.css';
import '../../css/u/uqwft5hcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<g class="ft5dv1b6b"><path class="j1-l-5b8u"/><path class="uqwft5hcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bowling" {...props}></Icon>
