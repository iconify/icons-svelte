<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjnt2fbgz.css';
import '../../css/x/xinwgk1sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rjnt2fbgz"/><path class="xinwgk1sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-tax-20" {...props}></Icon>
