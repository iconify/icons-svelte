<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vttjpyben.css';
import '../../css/c/c4mkapibv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vttjpyben"/><path class="c4mkapibv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pen-sparkle-20-bold" {...props}></Icon>
