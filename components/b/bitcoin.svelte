<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpja5bb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpja5bb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bitcoin" {...props}></Icon>
