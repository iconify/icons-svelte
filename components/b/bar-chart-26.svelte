<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clusz_b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="clusz_b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-26" {...props}></Icon>
