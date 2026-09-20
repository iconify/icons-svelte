<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1ucqd-cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1ucqd-cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:alarm-clock-minus-sharp" {...props}></Icon>
