<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4zeb_b-f.css';
import '../../css/a/aihie_dzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4zeb_b-f"/><path class="aihie_dzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-right-bold-duotone" {...props}></Icon>
