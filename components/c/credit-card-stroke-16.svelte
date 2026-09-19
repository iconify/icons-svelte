<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qst2e4_nj.css';
import '../../css/w/w7a4y5boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="qst2e4_nj"/><path class="w7a4y5boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:credit-card-stroke-16" {...props}></Icon>
