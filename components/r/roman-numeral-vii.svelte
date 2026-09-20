<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxmp_-hzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lxmp_-hzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-vii" {...props}></Icon>
