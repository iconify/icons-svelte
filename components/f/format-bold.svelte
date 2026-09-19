<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al76bac_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":232,"height":384};
const content = `<path class="al76bac_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-bold" {...props}></Icon>
