<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o65e3xbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o65e3xbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-sparkles-solid" {...props}></Icon>
