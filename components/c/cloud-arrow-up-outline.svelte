<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo1euzr0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo1euzr0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cloud-arrow-up-outline" {...props}></Icon>
