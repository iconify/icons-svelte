<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjc1-ubhn.css';
import '../../css/w/wtz7xm9oe.css';
import '../../css/x/x9f35ubbf.css';
import '../../css/f/f4g37sbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sjc1-ubhn"/><path class="wtz7xm9oe"/><path class="x9f35ubbf"/><path class="f4g37sbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:port-20" {...props}></Icon>
