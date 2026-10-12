<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jisgs1lqi.css';
import '../../css/u/uktn-1b8e.css';
import '../../css/n/nq5_p_bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jisgs1lqi"/><path class="uktn-1b8e"/><path class="nq5_p_bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-alert-20" {...props}></Icon>
