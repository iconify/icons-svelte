<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm3s18ekn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gm3s18ekn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:construction" {...props}></Icon>
