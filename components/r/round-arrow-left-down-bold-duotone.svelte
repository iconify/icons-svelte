<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtmuzrg2o.css';
import '../../css/k/kcxg56bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path class="kcxg56bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-left-down-bold-duotone" {...props}></Icon>
