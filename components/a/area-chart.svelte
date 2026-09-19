<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ontcflkoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="ontcflkoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:area-chart" {...props}></Icon>
