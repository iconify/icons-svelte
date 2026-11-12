<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df_0m4b0p.css';
import '../../css/w/wd3q3wb6b.css';
import '../../css/v/v9uawug3k.css';
import '../../css/f/fm8efkbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="df_0m4b0p"/><path class="wd3q3wb6b"/><path class="v9uawug3k"/><path class="fm8efkbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:fluxcd-wordmark" {...props}></Icon>
