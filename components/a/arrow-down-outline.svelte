<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o88emhyfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o88emhyfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-down-outline" {...props}></Icon>
