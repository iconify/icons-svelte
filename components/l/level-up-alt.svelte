<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8adc4r9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q8adc4r9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:level-up-alt" {...props}></Icon>
