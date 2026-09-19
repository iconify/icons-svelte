<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itc5zdbai.css';
import '../../css/r/rk-x6tbbo.css';
import '../../css/z/zayszsbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itc5zdbai"/><path class="rk-x6tbbo"/><path class="zayszsbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-help-outline" {...props}></Icon>
