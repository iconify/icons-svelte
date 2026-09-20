<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw9uy4btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jw9uy4btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudnativepg-dark" {...props}></Icon>
