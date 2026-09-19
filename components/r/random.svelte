<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9f-_9bvl.css';
import '../../css/x/x0ujedc_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="r9f-_9bvl"/><path class="x0ujedc_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:random" {...props}></Icon>
