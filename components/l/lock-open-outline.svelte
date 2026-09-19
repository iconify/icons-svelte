<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwuy1sbez.css';
import '../../css/f/ff9jhsbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwuy1sbez"/><rect class="ff9jhsbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:lock-open-outline" {...props}></Icon>
