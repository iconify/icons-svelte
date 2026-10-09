<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a12gsqhdy.css';
import '../../css/e/ec3h0kz8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a12gsqhdy"/><path class="ec3h0kz8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pack-20-bold" {...props}></Icon>
