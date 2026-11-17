<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km5wu5wyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km5wu5wyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:carets-from-axis-dashed-vertical" {...props}></Icon>
