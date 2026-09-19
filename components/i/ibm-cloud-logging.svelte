<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm_s39bqo.css';
import '../../css/b/bf32wh85n.css';
import '../../css/l/li_wjjrfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lm_s39bqo"/><path class="bf32wh85n"/><path class="li_wjjrfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-logging" {...props}></Icon>
