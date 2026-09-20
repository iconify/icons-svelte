<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibczavbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ibczavbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bell-solid" {...props}></Icon>
