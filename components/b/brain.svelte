<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_1j10-np.css';
import '../../css/r/r2nonpb-r.css';
import '../../css/l/lhyk42bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_1j10-np wm-a"/><path class="r2nonpb-r wm-a"/><path class="lhyk42bxl wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:brain" {...props}></Icon>
