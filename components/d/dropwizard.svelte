<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgyi2j3xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xgyi2j3xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dropwizard" {...props}></Icon>
