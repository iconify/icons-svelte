<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cebhfqb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cebhfqb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:container-hub" {...props}></Icon>
