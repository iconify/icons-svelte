<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvgr61b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="zvgr61b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:phone" {...props}></Icon>
