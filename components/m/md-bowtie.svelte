<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njc6web4n.css';
import '../../css/i/iqll_cgam.css';
import '../../css/i/i5ggx7ltg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="njc6web4n"/><path class="iqll_cgam"/><path class="i5ggx7ltg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-bowtie" {...props}></Icon>
