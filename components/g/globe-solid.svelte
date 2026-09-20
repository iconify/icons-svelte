<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegqqvbgf.css';
import '../../css/d/di6z7bc9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oegqqvbgf"/><path class="di6z7bc9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:globe-solid" {...props}></Icon>
