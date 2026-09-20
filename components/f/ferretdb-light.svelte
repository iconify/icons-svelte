<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t96x9qtfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t96x9qtfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ferretdb-light" {...props}></Icon>
