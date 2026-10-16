<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn1dkmnqu.css';
import '../../css/t/th0-odbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mn1dkmnqu"/><path class="th0-odbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:axe-20-bold" {...props}></Icon>
