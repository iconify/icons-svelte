<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0-wepb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a0-wepb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-tc-square" {...props}></Icon>
