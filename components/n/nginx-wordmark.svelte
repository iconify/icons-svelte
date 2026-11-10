<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp1ojc_zq.css';
import '../../css/n/nucjxzbql.css';
import '../../css/u/uz5m12bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tp1ojc_zq"/><path class="nucjxzbql"/><path class="uz5m12bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nginx-wordmark" {...props}></Icon>
