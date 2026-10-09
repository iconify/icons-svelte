<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k48mo0bik.css';
import '../../css/u/u1ifhyb-o.css';
import '../../css/t/t7x_kqnwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k48mo0bik"/><path class="u1ifhyb-o"/><path class="t7x_kqnwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:belt-drive-48-bold" {...props}></Icon>
