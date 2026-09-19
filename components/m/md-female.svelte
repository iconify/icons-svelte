<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeultby5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oeultby5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-female" {...props}></Icon>
