<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmmo2nbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qmmo2nbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:ellipsis" {...props}></Icon>
