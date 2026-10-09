<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t170-qrdh.css';
import '../../css/u/uto33fc8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t170-qrdh"/><path class="uto33fc8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:at-sign-20" {...props}></Icon>
