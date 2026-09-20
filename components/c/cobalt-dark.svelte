<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjciqdb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjciqdb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cobalt-dark" {...props}></Icon>
