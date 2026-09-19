<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrdy0obbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrdy0obbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:command-solid" {...props}></Icon>
