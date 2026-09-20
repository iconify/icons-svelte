<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t59excn8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t59excn8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:floppy-disk-1" {...props}></Icon>
