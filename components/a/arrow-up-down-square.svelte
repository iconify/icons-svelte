<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/samxp0zez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="samxp0zez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-down-square" {...props}></Icon>
