<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6i2hsbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6i2hsbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-off-filled" {...props}></Icon>
