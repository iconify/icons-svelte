<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhc3qnbeu.css';
import '../../css/z/zv-53k7bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhc3qnbeu"/><path class="zv-53k7bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-nutrition" {...props}></Icon>
