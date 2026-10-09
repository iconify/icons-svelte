<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdy5yl5us.css';
import '../../css/k/kanbl39ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gdy5yl5us"/><path class="kanbl39ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-20-bold" {...props}></Icon>
