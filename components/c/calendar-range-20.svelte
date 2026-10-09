<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4_udjxz.css';
import '../../css/a/anrgkxx6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ti4_udjxz"/><path class="anrgkxx6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-range-20" {...props}></Icon>
