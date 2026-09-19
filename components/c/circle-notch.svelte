<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmq_q9baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kmq_q9baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-notch" {...props}></Icon>
