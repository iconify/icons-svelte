<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aadq953xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aadq953xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:plug-solid" {...props}></Icon>
