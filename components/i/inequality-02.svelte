<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1h-0dbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1h-0dbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:inequality-02" {...props}></Icon>
