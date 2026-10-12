<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta5f1hbwd.css';
import '../../css/r/r-bb6_b2h.css';
import '../../css/e/ehrnxuvhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ta5f1hbwd"/><path class="r-bb6_b2h"/><path class="ehrnxuvhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pig-48-bold" {...props}></Icon>
