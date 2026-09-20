<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcxxl1c-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xcxxl1c-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invio" {...props}></Icon>
