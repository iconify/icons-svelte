<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1tcy5bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c1tcy5bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:indent-20" {...props}></Icon>
