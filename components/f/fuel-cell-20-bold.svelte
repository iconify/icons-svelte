<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9fygebyi.css';
import '../../css/p/pw602pb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e9fygebyi"/><path class="pw602pb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-cell-20-bold" {...props}></Icon>
