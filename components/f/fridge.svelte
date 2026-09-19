<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiep-3mai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiep-3mai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fridge" {...props}></Icon>
