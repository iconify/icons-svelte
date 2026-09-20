<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbz9xohyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbz9xohyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-check-line" {...props}></Icon>
