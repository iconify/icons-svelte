<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_hiasb3j.css';
import '../../css/z/zme2kfuvy.css';
import '../../css/j/joilwmbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_hiasb3j"/><path class="zme2kfuvy"/><path class="joilwmbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cement-plant-20-bold" {...props}></Icon>
