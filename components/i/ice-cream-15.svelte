<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc97kzb0z.css';
import '../../css/s/sgq67hbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mc97kzb0z"/><path class="sgq67hbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:ice-cream-15" {...props}></Icon>
