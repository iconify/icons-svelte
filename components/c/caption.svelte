<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj_ko-1ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_ko-1ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:caption" {...props}></Icon>
