<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb_59depv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_59depv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:arcade" {...props}></Icon>
