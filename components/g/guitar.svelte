<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu-50lb7t.css';
import '../../css/b/brgqastdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iu-50lb7t"/><path class="brgqastdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:guitar" {...props}></Icon>
