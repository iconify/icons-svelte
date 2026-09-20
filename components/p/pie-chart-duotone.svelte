<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdco8y64r.css';
import '../../css/t/ttpvcybxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdco8y64r"/><path class="ttpvcybxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pie-chart-duotone" {...props}></Icon>
