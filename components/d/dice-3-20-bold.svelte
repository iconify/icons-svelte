<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfgcicctr.css';
import '../../css/s/s4kbfzbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfgcicctr"/><path class="s4kbfzbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dice-3-20-bold" {...props}></Icon>
