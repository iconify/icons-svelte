<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu22fmb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu22fmb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:palette-solid" {...props}></Icon>
