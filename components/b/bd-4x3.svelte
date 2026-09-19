<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2x54nbfw.css';
import '../../css/c/c41bz1boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="l2x54nbfw"/><circle class="c41bz1boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bd-4x3" {...props}></Icon>
