<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwe291bsk.css';
import '../../css/m/mgz4g1bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mwe291bsk"/><path class="mgz4g1bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:eye-minus" {...props}></Icon>
