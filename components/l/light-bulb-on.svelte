<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_2q0_01r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_2q0_01r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:light-bulb-on" {...props}></Icon>
