<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnw4jqz8j.css';
import '../../css/u/uwp-39bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gnw4jqz8j"/><path class="uwp-39bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:milestone-20" {...props}></Icon>
