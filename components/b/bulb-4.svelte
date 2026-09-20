<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr_rigy-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="hr_rigy-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bulb-4" {...props}></Icon>
