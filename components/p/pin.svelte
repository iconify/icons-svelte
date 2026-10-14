<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm7uaeb1c.css';
import '../../css/t/tc3e2jyph.css';
import '../../css/l/l0ij5ccyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="rm7uaeb1c"><path class="tc3e2jyph"/><path class="l0ij5ccyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:pin" {...props}></Icon>
