<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmf4webcc.css';
import '../../css/n/ngr5oebfg.css';
import '../../css/a/a8noj8_gi.css';
import '../../css/g/g38ac68gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmf4webcc"/><path class="ngr5oebfg"/><path class="a8noj8_gi"/><path class="g38ac68gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:discopanel-light" {...props}></Icon>
