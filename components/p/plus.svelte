<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1m7vvbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1m7vvbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:plus" {...props}></Icon>
