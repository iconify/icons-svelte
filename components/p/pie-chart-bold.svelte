<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqk9_4b2a.css';
import '../../css/r/r-rt-5hka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqk9_4b2a"/><path class="r-rt-5hka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pie-chart-bold" {...props}></Icon>
