<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk1mbvbfk.css';
import '../../css/b/b4-fwcc_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="yk1mbvbfk"/><path class="b4-fwcc_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-imaging-alternative-mri" {...props}></Icon>
