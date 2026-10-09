<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezhonm73e.css';
import '../../css/v/vck8c0qcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ezhonm73e"/><path class="vck8c0qcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:esg-report-20" {...props}></Icon>
