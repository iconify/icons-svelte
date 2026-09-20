<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf3e5ykvo.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/w/wplkh7x2z.css';
import '../../css/z/zsll00blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="kf3e5ykvo"/><g class="brzn_0bpr"><circle class="wplkh7x2z"/><path class="zsll00blu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:disappointed-face" {...props}></Icon>
