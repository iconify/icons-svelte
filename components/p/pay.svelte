<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du68bibwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="du68bibwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pay" {...props}></Icon>
