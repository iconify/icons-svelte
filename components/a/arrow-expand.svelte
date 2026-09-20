<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhbtkac8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qhbtkac8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-expand" {...props}></Icon>
