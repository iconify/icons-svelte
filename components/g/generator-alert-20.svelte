<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le62_1bgw.css';
import '../../css/w/wikar0bxx.css';
import '../../css/n/nq5_p_bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="le62_1bgw"/><path class="wikar0bxx"/><path class="nq5_p_bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:generator-alert-20" {...props}></Icon>
