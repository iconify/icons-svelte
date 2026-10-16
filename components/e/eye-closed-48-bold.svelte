<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2zqenb_d.css';
import '../../css/t/tvzdim3hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2zqenb_d"/><path class="tvzdim3hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-closed-48-bold" {...props}></Icon>
