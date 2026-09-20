<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec1mt9fwb.css';
import '../../css/h/h2sed2fvb.css';
import '../../css/n/nt1eozdqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec1mt9fwb"/><path class="h2sed2fvb"/><path class="nt1eozdqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-badge-24" {...props}></Icon>
