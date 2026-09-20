<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxw9d-z9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dxw9d-z9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:linkedin-outline" {...props}></Icon>
