<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_l0y2buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x_l0y2buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bulk-upload" {...props}></Icon>
