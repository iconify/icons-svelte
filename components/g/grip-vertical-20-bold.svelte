<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn493gz6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gn493gz6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grip-vertical-20-bold" {...props}></Icon>
