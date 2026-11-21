<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0mcxk10l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0mcxk10l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docker-dark" {...props}></Icon>
