<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwlbydusy.css';
import '../../css/f/fshg12b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwlbydusy"/><path class="fshg12b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:download-24" {...props}></Icon>
