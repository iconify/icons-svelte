<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxllr2mpy.css';
import '../../css/q/q3acjfbyd.css';
import '../../css/k/kzer2rmvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxllr2mpy"/><path class="q3acjfbyd"/><path class="kzer2rmvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flange-20-bold" {...props}></Icon>
