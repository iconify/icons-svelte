<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7qi5pmcg.css';
import '../../css/b/b7scrfump.css';
import '../../css/b/b-tlngp_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7qi5pmcg"/><path class="b7scrfump"/><path class="b-tlngp_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-pills-bold-duotone" {...props}></Icon>
