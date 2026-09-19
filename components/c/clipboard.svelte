<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4-yxccww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="k4-yxccww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:clipboard" {...props}></Icon>
