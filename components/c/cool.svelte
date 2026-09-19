<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a36kvcc-u.css';
import '../../css/h/hm1y73b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a36kvcc-u"/><path class="hm1y73b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:cool" {...props}></Icon>
