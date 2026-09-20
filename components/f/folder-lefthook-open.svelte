<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u48mzcbuj.css';
import '../../css/j/jx1k9cbwn.css';
import '../../css/h/hpqa_4g6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u48mzcbuj"/><path class="jx1k9cbwn"/><path class="hpqa_4g6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-lefthook-open" {...props}></Icon>
