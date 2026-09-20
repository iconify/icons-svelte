<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyb-4acmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="qyb-4acmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-left" {...props}></Icon>
