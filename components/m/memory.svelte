<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba19-vb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ba19-vb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:memory" {...props}></Icon>
