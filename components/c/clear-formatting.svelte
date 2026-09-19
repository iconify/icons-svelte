<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi3p-9b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi3p-9b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:clear-formatting" {...props}></Icon>
