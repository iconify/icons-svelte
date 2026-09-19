<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz98m2akc.css';
import '../../css/k/kbbue1bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mz98m2akc"/><path class="kbbue1bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bus-sharp" {...props}></Icon>
