<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhj_kjb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhj_kjb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:angle-double-down" {...props}></Icon>
