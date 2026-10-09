<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_918vwrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f_918vwrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-right-48-bold" {...props}></Icon>
