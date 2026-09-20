<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4qvaultt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="s4qvaultt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bulb-2" {...props}></Icon>
