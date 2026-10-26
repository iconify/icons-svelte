<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih6hr7r5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ih6hr7r5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:godonateme" {...props}></Icon>
