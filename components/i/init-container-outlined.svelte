<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2mbsmb2r.css';
import '../../css/x/xyie74fxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2mbsmb2r"/><path class="xyie74fxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:init-container-outlined" {...props}></Icon>
