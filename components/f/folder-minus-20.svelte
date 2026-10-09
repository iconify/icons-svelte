<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk8kloxbh.css';
import '../../css/t/tn9fdubiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jk8kloxbh"/><path class="tn9fdubiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-minus-20" {...props}></Icon>
