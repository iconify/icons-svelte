<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv1mxrgyg.css';
import '../../css/h/h2tie5wrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv1mxrgyg"/><path class="h2tie5wrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:chart-line-solid" {...props}></Icon>
