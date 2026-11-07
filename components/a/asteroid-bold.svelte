<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq1o4rbim.css';
import '../../css/b/b1o-4174v.css';
import '../../css/c/cu88vc6ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq1o4rbim"/><path class="b1o-4174v"/><path class="cu88vc6ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:asteroid-bold" {...props}></Icon>
