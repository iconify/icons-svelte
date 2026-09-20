<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnfnpw1di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":405.1,"height":100};
const content = `<path class="rnfnpw1di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nintendo-light" {...props}></Icon>
