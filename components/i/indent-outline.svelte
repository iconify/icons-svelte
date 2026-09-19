<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux27x7bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux27x7bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:indent-outline" {...props}></Icon>
