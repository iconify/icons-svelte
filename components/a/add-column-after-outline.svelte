<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7qdf8b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7qdf8b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:add-column-after-outline" {...props}></Icon>
