<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/v/vj271db3h.css';
import '../../css/b/b1eoogomv.css';
import '../../css/u/um80ms1wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="vj271db3h"/><path class="b1eoogomv"/><path class="um80ms1wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-archive-bold-duotone" {...props}></Icon>
