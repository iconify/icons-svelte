<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9pq-abme.css';
import '../../css/k/k-6wvukge.css';
import '../../css/c/c30ngsbte.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/d/d0fw57ehj.css';
import '../../css/u/uey6unb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="k9pq-abme"><circle class="k-6wvukge"/><path class="c30ngsbte"/></g><g class="brzn_0bpr"><circle class="d0fw57ehj"/><path class="uey6unb3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:man-cartwheeling-medium-skin-tone" {...props}></Icon>
