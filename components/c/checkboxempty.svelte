<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv2zpyesr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":591,"height":677};
const content = `<path class="pv2zpyesr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:checkboxempty" {...props}></Icon>
