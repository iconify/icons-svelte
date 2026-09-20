<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxrhbebwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zxrhbebwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:html5-outline" {...props}></Icon>
