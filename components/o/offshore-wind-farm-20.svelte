<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enxtphbky.css';
import '../../css/n/n4d5fac5i.css';
import '../../css/u/u6c3ru_1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="enxtphbky"/><path class="n4d5fac5i"/><path class="u6c3ru_1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-wind-farm-20" {...props}></Icon>
