<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emm9a3bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emm9a3bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circle-dashed-20-bold" {...props}></Icon>
