<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b19yjd4da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b19yjd4da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:frame-solid" {...props}></Icon>
