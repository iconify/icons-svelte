<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-4cv_cxz.css';
import '../../css/v/v5r_03b1l.css';
import '../../css/r/rsodfxbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="h-4cv_cxz"/><path class="v5r_03b1l"/><path class="rsodfxbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:cameroon" {...props}></Icon>
