<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ialerhe_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ialerhe_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-1" {...props}></Icon>
