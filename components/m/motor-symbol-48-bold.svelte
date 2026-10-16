<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf_iwi87h.css';
import '../../css/v/vc8qn24vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tf_iwi87h"/><path class="vc8qn24vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:motor-symbol-48-bold" {...props}></Icon>
