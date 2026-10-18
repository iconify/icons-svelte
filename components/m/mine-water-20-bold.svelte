<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw96d85ov.css';
import '../../css/i/i1_yy39iv.css';
import '../../css/a/agaffo5ho.css';
import '../../css/p/pmviisk7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aw96d85ov"/><path class="i1_yy39iv"/><path class="agaffo5ho"/><path class="pmviisk7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-water-20-bold" {...props}></Icon>
