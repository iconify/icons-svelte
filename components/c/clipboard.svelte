<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ctc8bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="q2ctc8bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:clipboard" {...props}></Icon>
