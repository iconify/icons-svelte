<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi4280bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":628,"height":717};
const content = `<path class="oi4280bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:present" {...props}></Icon>
