<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbpwmytgh.css';
import '../../css/m/m6omgn3hc.css';
import '../../css/f/fbqsjxnbt.css';
import '../../css/q/qho2-b78i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jbpwmytgh"/><path class="m6omgn3hc"/><path class="fbqsjxnbt"/><path class="qho2-b78i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forest-20-bold" {...props}></Icon>
