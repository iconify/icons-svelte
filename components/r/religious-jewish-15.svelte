<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btcpoi1uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="btcpoi1uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-jewish-15" {...props}></Icon>
