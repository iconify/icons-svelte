<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8jkvsbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8jkvsbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:monitor-line" {...props}></Icon>
