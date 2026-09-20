<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdfevou9k.css';
import '../../css/h/hfrzhebxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qdfevou9k"/><path class="hfrzhebxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:briefcase-solid" {...props}></Icon>
