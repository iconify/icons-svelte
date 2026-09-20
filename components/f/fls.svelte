<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/citlsybef.css';
import '../../css/k/kd8sdbbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="citlsybef"/><path class="kd8sdbbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fls" {...props}></Icon>
