<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk40dd1ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uk40dd1ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-customchar" {...props}></Icon>
