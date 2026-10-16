<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgjp5_b_u.css';
import '../../css/k/kwy2wr4ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="kwy2wr4ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-oil-20" {...props}></Icon>
