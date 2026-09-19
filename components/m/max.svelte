<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q95_q6bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q95_q6bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:max" {...props}></Icon>
