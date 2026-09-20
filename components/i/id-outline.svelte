<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo1xnyukw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xo1xnyukw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:id-outline" {...props}></Icon>
