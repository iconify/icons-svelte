<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlkpbe_sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mlkpbe_sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jack-o-lantern" {...props}></Icon>
