<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub-8msbxg.css';
import '../../css/u/u68we71_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="ub-8msbxg"/><path class="u68we71_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chair-filled" {...props}></Icon>
