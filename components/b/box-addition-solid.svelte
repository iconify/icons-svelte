<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-2h97zdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x-2h97zdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:box-addition-solid" {...props}></Icon>
