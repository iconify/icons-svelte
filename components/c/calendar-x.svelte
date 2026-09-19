<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuqwpyirs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuqwpyirs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-x" {...props}></Icon>
