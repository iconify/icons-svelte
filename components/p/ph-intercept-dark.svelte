<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgcdo-zfb.css';
import '../../css/u/ufos4gbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgcdo-zfb"/><path class="ufos4gbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ph-intercept-dark" {...props}></Icon>
