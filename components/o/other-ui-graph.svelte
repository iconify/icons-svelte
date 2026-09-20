<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgsklfbyu.css';
import '../../css/d/d516lezif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rgsklfbyu"/><path class="d516lezif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-graph" {...props}></Icon>
