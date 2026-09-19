<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf7w_yagv.css';
import '../../css/c/c834y5bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lf7w_yagv"/><path class="c834y5bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bus" {...props}></Icon>
