<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxef4ibam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":752};
const content = `<path class="lxef4ibam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:5" {...props}></Icon>
