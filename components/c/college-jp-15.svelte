<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg8cfboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lsg8cfboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:college-jp-15" {...props}></Icon>
