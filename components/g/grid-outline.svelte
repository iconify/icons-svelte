<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laovnacfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laovnacfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:grid-outline" {...props}></Icon>
