<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwt9jbbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwt9jbbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brackets-contain" {...props}></Icon>
