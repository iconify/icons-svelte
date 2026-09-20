<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8x9zbc8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8x9zbc8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:broadcom" {...props}></Icon>
