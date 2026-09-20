<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioq81ya0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ioq81ya0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lifebuoy-solid" {...props}></Icon>
