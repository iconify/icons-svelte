<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s69k6bb7h.css';
import '../../css/o/ofyi6pbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s69k6bb7h"/><path class="ofyi6pbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-cylinder-20-bold" {...props}></Icon>
