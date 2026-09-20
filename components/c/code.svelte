<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghra1q62g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ghra1q62g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:code" {...props}></Icon>
