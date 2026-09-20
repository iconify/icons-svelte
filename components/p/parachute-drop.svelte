<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kck5-abkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kck5-abkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:parachute-drop" {...props}></Icon>
