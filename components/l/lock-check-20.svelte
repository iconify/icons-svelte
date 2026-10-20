<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g--bxo5in.css';
import '../../css/x/xxzut0e2z.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g--bxo5in"/><path class="xxzut0e2z"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-check-20" {...props}></Icon>
