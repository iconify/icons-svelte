<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_2q19p9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_2q19p9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:motion-sensor-temperature" {...props}></Icon>
