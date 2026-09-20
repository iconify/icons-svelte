<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksw8ll90a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksw8ll90a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:close" {...props}></Icon>
