<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh1gyn4rx.css';
import '../../css/d/dh_lsrzrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nh1gyn4rx"/><path class="dh_lsrzrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-card-20" {...props}></Icon>
