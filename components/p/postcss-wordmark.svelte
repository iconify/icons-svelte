<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt_jtfb1h.css';
import '../../css/g/gw8h__b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mt_jtfb1h"/><path class="gw8h__b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:postcss-wordmark" {...props}></Icon>
