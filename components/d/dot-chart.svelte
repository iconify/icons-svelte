<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an8hljbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="an8hljbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:dot-chart" {...props}></Icon>
