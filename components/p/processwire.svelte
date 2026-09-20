<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp61kpbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp61kpbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:processwire" {...props}></Icon>
