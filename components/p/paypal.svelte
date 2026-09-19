<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gezopnizk.css';
import '../../css/p/plqzk5bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gezopnizk"/><path class="plqzk5bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:paypal" {...props}></Icon>
