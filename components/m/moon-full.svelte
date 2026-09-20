<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzo-pjbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wzo-pjbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:moon-full" {...props}></Icon>
