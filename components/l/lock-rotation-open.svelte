<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgw0qblsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lgw0qblsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lock-rotation-open" {...props}></Icon>
