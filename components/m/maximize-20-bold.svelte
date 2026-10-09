<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbld8bbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rbld8bbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:maximize-20-bold" {...props}></Icon>
