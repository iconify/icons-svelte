<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr1eulbdl.css';
import '../../css/z/z6nvbo_3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr1eulbdl"/><path class="z6nvbo_3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-double-up-alt" {...props}></Icon>
