<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlom9koql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tlom9koql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:pencil-solid" {...props}></Icon>
