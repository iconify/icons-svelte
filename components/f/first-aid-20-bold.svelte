<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0m9rc9my.css';
import '../../css/o/o2332zble.css';
import '../../css/k/kg73c9ijz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j0m9rc9my"/><path class="o2332zble"/><path class="kg73c9ijz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:first-aid-20-bold" {...props}></Icon>
