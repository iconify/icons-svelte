<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuvri7gtn.css';
import '../../css/m/mtplmt03a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuvri7gtn"/><path class="mtplmt03a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-check-bold-duotone" {...props}></Icon>
