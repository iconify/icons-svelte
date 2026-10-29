<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7k1ti8-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7k1ti8-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:loader-circle-solid" {...props}></Icon>
