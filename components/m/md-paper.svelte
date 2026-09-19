<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmtkp5byu.css';
import '../../css/j/jyj0czf8z.css';
import '../../css/a/a4_yhfdzc.css';
import '../../css/d/du2o76hwu.css';
import '../../css/r/rzbq2ac6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fmtkp5byu"/><path class="jyj0czf8z"/><path class="a4_yhfdzc"/><path class="du2o76hwu"/><path class="rzbq2ac6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-paper" {...props}></Icon>
