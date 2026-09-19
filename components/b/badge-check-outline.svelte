<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cal9kjb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cal9kjb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:badge-check-outline" {...props}></Icon>
