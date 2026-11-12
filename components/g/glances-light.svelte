<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jar70jbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jar70jbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glances-light" {...props}></Icon>
