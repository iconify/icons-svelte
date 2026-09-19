<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gln2ec9ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gln2ec9ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cube-solid" {...props}></Icon>
