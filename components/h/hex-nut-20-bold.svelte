<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7nqvkavv.css';
import '../../css/b/bu587_boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s7nqvkavv"/><path class="bu587_boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-nut-20-bold" {...props}></Icon>
