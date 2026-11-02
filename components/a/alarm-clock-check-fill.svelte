<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbhpq2bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbhpq2bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alarm-clock-check-fill" {...props}></Icon>
