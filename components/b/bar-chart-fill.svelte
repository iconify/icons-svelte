<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkf-l0edq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hkf-l0edq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bar-chart-fill" {...props}></Icon>
