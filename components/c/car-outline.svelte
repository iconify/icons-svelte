<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-klr3bdo.css';
import '../../css/e/e8icw_b4f.css';
import '../../css/w/ws9d_1b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-klr3bdo"/><path class="e8icw_b4f"/><path clip-rule="evenodd" class="ws9d_1b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:car-outline" {...props}></Icon>
