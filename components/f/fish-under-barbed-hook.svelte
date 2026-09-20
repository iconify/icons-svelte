<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7cbi6b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u7cbi6b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-under-barbed-hook" {...props}></Icon>
