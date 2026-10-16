<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyiqdq-1y.css';
import '../../css/e/ek3-3_91h.css';
import '../../css/f/fpc4qk6ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jyiqdq-1y"/><path class="ek3-3_91h"/><path class="fpc4qk6ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-burner-20-bold" {...props}></Icon>
