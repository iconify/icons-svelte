<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq_yi2-xa.css';
import '../../css/g/gusqowxtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="dq_yi2-xa"/><path class="gusqowxtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:css-new" {...props}></Icon>
