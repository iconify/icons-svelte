<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h219x64vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h219x64vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pf2etools-dark" {...props}></Icon>
