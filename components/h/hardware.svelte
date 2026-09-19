<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjh1bacdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="qjh1bacdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:hardware" {...props}></Icon>
