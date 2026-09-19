<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2s6roafe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2s6roafe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:chevron-down" {...props}></Icon>
