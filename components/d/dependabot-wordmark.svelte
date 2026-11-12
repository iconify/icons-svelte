<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_lja2bcd.css';
import '../../css/w/wmnla3ben.css';
import '../../css/p/ppxb-5bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="p_lja2bcd"/><path class="wmnla3ben"/><path class="ppxb-5bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dependabot-wordmark" {...props}></Icon>
