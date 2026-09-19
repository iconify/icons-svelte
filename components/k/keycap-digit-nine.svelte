<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm5c6wbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zm5c6wbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-nine" {...props}></Icon>
