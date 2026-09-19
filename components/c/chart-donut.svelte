<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8jaru_ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q8jaru_ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chart-donut" {...props}></Icon>
