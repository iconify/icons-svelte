<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czsubus_w.css';
import '../../css/r/rfqi4njim.css';
import '../../css/b/b6fhfryel.css';
import '../../css/c/c3v_g_mjq.css';
import '../../css/c/c-jdkp9ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="czsubus_w"/><circle class="rfqi4njim"/><path class="b6fhfryel"/><circle class="c3v_g_mjq"/><path class="c-jdkp9ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watsonx-code-assistant-for-z-refactor" {...props}></Icon>
