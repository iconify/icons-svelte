<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs2ycjb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xs2ycjb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:encryption" {...props}></Icon>
