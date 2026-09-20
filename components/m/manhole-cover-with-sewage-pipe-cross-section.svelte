<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcifvji8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vcifvji8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:manhole-cover-with-sewage-pipe-cross-section" {...props}></Icon>
