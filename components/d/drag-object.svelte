<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uprmt5bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uprmt5bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:drag-object" {...props}></Icon>
