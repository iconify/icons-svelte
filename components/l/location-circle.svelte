<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sujs77bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="sujs77bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:location-circle" {...props}></Icon>
