<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moibuabky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="moibuabky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-20" {...props}></Icon>
