<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejshfpu0b.css';
import '../../css/p/pm7rgls4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":260,"height":260};
const content = `<path class="ejshfpu0b"/><path class="pm7rgls4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:conceptboard" {...props}></Icon>
