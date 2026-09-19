<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5rcklbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5rcklbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-pause" {...props}></Icon>
