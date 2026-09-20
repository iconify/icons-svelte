<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh11dfbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kh11dfbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:alarm-outline" {...props}></Icon>
