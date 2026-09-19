<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__43in4h.css';
import '../../css/u/ub90ksf3r.css';
import '../../css/v/vi2s80h4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="a__43in4h"/><path class="ub90ksf3r"/><path class="vi2s80h4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:redis" {...props}></Icon>
