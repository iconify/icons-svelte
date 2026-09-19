<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7-6b3kbh.css';
import '../../css/x/xnaxp_oyy.css';
import '../../css/m/mj3jpacnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f7-6b3kbh"/><path class="xnaxp_oyy"/><path class="mj3jpacnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:model-s" {...props}></Icon>
