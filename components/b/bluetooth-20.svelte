<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t27q67qpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t27q67qpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bluetooth-20" {...props}></Icon>
