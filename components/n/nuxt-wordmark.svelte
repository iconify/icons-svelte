<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwf_b-maa.css';
import '../../css/i/iu0_yp7rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gwf_b-maa"/><path class="iu0_yp7rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nuxt-wordmark" {...props}></Icon>
