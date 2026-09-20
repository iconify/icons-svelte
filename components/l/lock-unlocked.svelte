<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo2qolbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mo2qolbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lock-unlocked" {...props}></Icon>
