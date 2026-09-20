<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt1pn2bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="lt1pn2bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chevron-down-double" {...props}></Icon>
