<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hem1ktbzj.css';
import '../../css/v/v--qb2bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hem1ktbzj wm-k"/><path class="v--qb2bdl wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:corner-down-right" {...props}></Icon>
